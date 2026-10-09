<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faw1_xb-c.css';
import '../../css/d/dyv57sbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="faw1_xb-c"/><path class="dyv57sbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fusion-48" {...props}></Icon>
