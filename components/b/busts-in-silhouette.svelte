<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4oym9cew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e4oym9cew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:busts-in-silhouette" {...props}></Icon>
