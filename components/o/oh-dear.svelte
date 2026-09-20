<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmai-rcjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmai-rcjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:oh-dear" {...props}></Icon>
