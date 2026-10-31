<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lgf7rpbof.css';
import '../../css/g/gbyjw7b_q.css';
import '../../css/g/gx73n_bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lgf7rpbof wm-shadow"/><path class="gbyjw7b_q wm-shadow"/><path class="gx73n_bub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:person-standing" {...props}></Icon>
