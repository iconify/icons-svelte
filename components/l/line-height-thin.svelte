<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk7rjrwsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xk7rjrwsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:line-height-thin" {...props}></Icon>
