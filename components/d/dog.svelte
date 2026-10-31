<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/i/isc99_d8g.css';
import '../../css/o/on9kbqb3p.css';
import '../../css/i/i6vz6ibrb.css';
import '../../css/w/wseixtb1u.css';
import '../../css/v/vjr8b9jwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="isc99_d8g"/><path class="on9kbqb3p wm-shine"/><path class="i6vz6ibrb wm-k"/><path class="wm-a wseixtb1u"/><path class="vjr8b9jwh wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:dog" {...props}></Icon>
