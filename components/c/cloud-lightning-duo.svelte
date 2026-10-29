<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/p0uuuh_ua.css';
import '../../css/a/ahlmu3bhe.css';
import '../../css/y/yxa0nhn1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="p0uuuh_ua"/><path class="ahlmu3bhe wm-a"/><path class="yxa0nhn1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:cloud-lightning-duo" {...props}></Icon>
