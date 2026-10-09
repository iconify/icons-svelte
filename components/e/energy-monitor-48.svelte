<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b63tvfb8j.css';
import '../../css/h/hutzz7vvf.css';
import '../../css/x/xno-yqkug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b63tvfb8j"/><path class="hutzz7vvf"/><path class="xno-yqkug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-monitor-48" {...props}></Icon>
