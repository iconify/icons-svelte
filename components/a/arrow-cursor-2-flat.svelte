<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp2cgibwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sp2cgibwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:arrow-cursor-2-flat" {...props}></Icon>
