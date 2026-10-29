<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/far50iw7l.css';
import '../../css/f/fs0yrab0m.css';
import '../../css/h/hffkpbehn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="far50iw7l wm-k"/><path class="fs0yrab0m wm-a"/><path class="hffkpbehn wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:disc" {...props}></Icon>
