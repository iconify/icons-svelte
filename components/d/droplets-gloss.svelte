<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w61v8s2md.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w61v8s2md"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:droplets-gloss" {...props}></Icon>
