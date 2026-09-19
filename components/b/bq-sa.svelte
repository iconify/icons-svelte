<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rp16bptoo.css';
import '../../css/v/vgl5229gh.css';
import '../../css/j/jdsh2qbwv.css';
import '../../css/b/bssikkbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="rp16bptoo"/><path class="vgl5229gh"/><path class="jdsh2qbwv"/><path class="bssikkbkz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:bq-sa" {...props}></Icon>
