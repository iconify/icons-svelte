<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj_40jb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":260,"height":256};
const content = `<path class="aj_40jb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:curseforge-light" {...props}></Icon>
