<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4m--tbpp.css';
import '../../css/i/ijgbmtb8w.css';
import '../../css/f/fiqktq5gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v4m--tbpp"/><path class="ijgbmtb8w"/><path class="fiqktq5gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lay-vessel-48" {...props}></Icon>
