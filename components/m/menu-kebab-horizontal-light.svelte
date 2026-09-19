<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcgi44bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcgi44bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-horizontal-light" {...props}></Icon>
