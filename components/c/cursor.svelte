<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owmm25bsk.css';
import '../../css/v/v8sc8rzsp.css';
import '../../css/m/meey0ablw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="owmm25bsk"/><path class="v8sc8rzsp"/><path class="meey0ablw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cursor" {...props}></Icon>
