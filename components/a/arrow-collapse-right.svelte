<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt4c_3bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt4c_3bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-collapse-right" {...props}></Icon>
