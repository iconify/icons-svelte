<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp8sdbcdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp8sdbcdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:key-alt-remove" {...props}></Icon>
