<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx3-iszcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx3-iszcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mxm" {...props}></Icon>
