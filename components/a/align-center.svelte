<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/b48f0ccsu.css';
import '../../css/x/x-g0wab5m.css';
import '../../css/h/h7g538bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="b48f0ccsu wm-shadow"/><path class="wm-shadow x-g0wab5m"/><path class="h7g538bxc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:align-center" {...props}></Icon>
