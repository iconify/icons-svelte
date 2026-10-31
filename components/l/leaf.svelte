<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/aa0449bjo.css';
import '../../css/d/dmeqm9b9o.css';
import '../../css/u/u-4o0pbez.css';
import '../../css/f/fbkhmwd0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="aa0449bjo wm-shadow"/><path class="dmeqm9b9o wm-shadow"/><path class="u-4o0pbez"/><path class="fbkhmwd0i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:leaf" {...props}></Icon>
