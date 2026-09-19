<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o93hmcaib.css';
import '../../css/q/q6u6gfbgw.css';
import '../../css/q/q-052gbrv.css';
import '../../css/y/yiy3jjqui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="o93hmcaib"/><path class="q6u6gfbgw"/><circle class="q-052gbrv"/><path class="yiy3jjqui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:disabled-picture" {...props}></Icon>
