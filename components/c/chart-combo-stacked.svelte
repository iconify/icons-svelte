<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3fziz2vw.css';
import '../../css/x/xtkqegbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f3fziz2vw"/><path class="xtkqegbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-combo-stacked" {...props}></Icon>
