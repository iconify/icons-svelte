<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuzkko4qn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuzkko4qn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-vertical-light" {...props}></Icon>
