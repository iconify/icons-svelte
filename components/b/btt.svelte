<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ir4y4fk6l.css';
import '../../css/m/md286fbip.css';
import '../../css/j/j1q8n0b_v.css';
import '../../css/q/qg_vemb-q.css';
import '../../css/c/c19b_rbpl.css';
import '../../css/g/g5v17fbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="ir4y4fk6l"/><g class="md286fbip"><path class="j1q8n0b_v"/><path class="qg_vemb-q"/><path class="c19b_rbpl"/><path class="g5v17fbzi"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:btt" {...props}></Icon>
