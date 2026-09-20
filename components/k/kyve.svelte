<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdhyr6bcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdhyr6bcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kyve" {...props}></Icon>
