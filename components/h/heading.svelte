<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/n/nna7eebvs.css';
import '../../css/g/g9e86pbfe.css';
import '../../css/l/l9zg203ti.css';
import '../../css/g/grfewgbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="nna7eebvs wm-shadow"/><path class="g9e86pbfe wm-shadow"/><path class="l9zg203ti"/><path class="grfewgbih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:heading" {...props}></Icon>
