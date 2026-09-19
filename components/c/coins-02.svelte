<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb68-hbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb68-hbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:coins-02" {...props}></Icon>
