<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nde3o9bjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nde3o9bjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:folder-thin" {...props}></Icon>
