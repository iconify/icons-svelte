<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/ndjbzvb7j.css';
import '../../css/f/fjughibva.css';
import '../../css/s/sc2tvobjv.css';
import '../../css/p/pi5wsnb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="ndjbzvb7j wm-shadow"/><path class="fjughibva wm-shadow"/><path class="sc2tvobjv"/><path class="pi5wsnb6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:rotate-cw" {...props}></Icon>
