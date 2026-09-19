<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz7yt3bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xz7yt3bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-spellcheck" {...props}></Icon>
