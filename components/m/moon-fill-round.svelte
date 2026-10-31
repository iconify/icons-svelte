<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chwt8zbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chwt8zbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:moon-fill-round" {...props}></Icon>
