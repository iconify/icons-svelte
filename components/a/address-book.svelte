<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mkmmjsq7w.css';
import '../../css/v/vsl3hzbif.css';
import '../../css/d/dt2ucwblp.css';
import '../../css/u/u9chh6_lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mkmmjsq7w"/><path class="vsl3hzbif"/><path class="dt2ucwblp"/><path class="u9chh6_lz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:address-book" {...props}></Icon>
