<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jbsmz5cgw.css';
import '../../css/i/ida3dz87g.css';
import '../../css/d/dxi3c3bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jbsmz5cgw"/><path class="ida3dz87g"/><path class="dxi3c3bdb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notification-bell-muted" {...props}></Icon>
