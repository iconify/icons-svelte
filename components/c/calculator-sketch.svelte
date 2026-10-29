<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/irsn4xb5r.css';
import '../../css/r/r338hqbsu.css';
import '../../css/l/lvjdmbcqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="irsn4xb5r"/><path class="r338hqbsu wm-k"/><path class="lvjdmbcqy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:calculator-sketch" {...props}></Icon>
