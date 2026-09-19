<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bidi4bbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bidi4bbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:cpu" {...props}></Icon>
