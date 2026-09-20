<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/y/yd6xyscff.css';
import '../../css/p/ppdb-46ij.css';
import '../../css/o/ob-stir9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect class="yd6xyscff"/><path class="ppdb-46ij"/><path class="ob-stir9j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:boxes" {...props}></Icon>
