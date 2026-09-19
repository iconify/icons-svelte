<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/r/rml6syxed.css';
import '../../css/p/pv0dl6bjc.css';
import '../../css/r/rrbbmlbwz.css';
import '../../css/u/un6xfgbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="bi12bsetm"><circle class="rml6syxed"/><path class="pv0dl6bjc"/><path class="rrbbmlbwz"/><path class="un6xfgbrp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:arnx" {...props}></Icon>
