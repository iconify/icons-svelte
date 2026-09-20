<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwj6fiudg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":260,"height":256};
const content = `<path class="iwj6fiudg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:curseforge-dark" {...props}></Icon>
