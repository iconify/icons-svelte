<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyng5hbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nyng5hbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:modsawup" {...props}></Icon>
