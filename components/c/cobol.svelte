<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvz1_m6rm.css';
import '../../css/c/c0nme4boi.css';
import '../../css/t/tqm4eob6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pvz1_m6rm"/><path class="c0nme4boi"/><path class="tqm4eob6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cobol" {...props}></Icon>
