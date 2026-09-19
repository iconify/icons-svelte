<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpsjndblj.css';
import '../../css/i/igk3ecc7a.css';
import '../../css/i/ihjfc8h8i.css';
import '../../css/d/doqds4bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gpsjndblj"/><path class="igk3ecc7a"/><path class="ihjfc8h8i"/><path class="doqds4bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lastquartermoon" {...props}></Icon>
