<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fupjxpble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fupjxpble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:note-edit-outline" {...props}></Icon>
