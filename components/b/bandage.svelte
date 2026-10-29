<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/adnxrhb5g.css';
import '../../css/p/p43mkbb9d.css';
import '../../css/y/y-xkudbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="adnxrhb5g"/><path class="p43mkbb9d wm-a"/><path class="wm-a y-xkudbrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bandage" {...props}></Icon>
