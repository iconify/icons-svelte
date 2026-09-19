<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg7g0cboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rg7g0cboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-close-thin" {...props}></Icon>
