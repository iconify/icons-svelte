<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ori7inbrr.css';
import '../../css/q/q116iryet.css';
import '../../css/v/vyt_0h-7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ori7inbrr"/><path class="q116iryet"/><path class="vyt_0h-7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-shaft-48" {...props}></Icon>
