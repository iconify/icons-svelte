<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0ux_1vag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0ux_1vag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-vertical-bold" {...props}></Icon>
