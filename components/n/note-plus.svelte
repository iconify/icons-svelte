<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd6744_hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd6744_hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:note-plus" {...props}></Icon>
