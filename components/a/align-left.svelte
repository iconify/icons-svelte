<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/m96f6qbnd.css';
import '../../css/i/i9fl8kbvz.css';
import '../../css/p/p41ig8b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="m96f6qbnd wm-shadow"/><path class="i9fl8kbvz wm-shadow"/><path class="p41ig8b8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:align-left" {...props}></Icon>
