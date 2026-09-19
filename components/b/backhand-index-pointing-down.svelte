<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhnei0p-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bhnei0p-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:backhand-index-pointing-down" {...props}></Icon>
