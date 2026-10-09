<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i48le1b7u.css';
import '../../css/o/ofb0s2_ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i48le1b7u"/><path class="ofb0s2_ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:image-20-bold" {...props}></Icon>
