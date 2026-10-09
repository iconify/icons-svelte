<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0wv7wb3z.css';
import '../../css/e/epk77cclf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p0wv7wb3z"/><path class="epk77cclf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:a-frame-48" {...props}></Icon>
