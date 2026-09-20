<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr_qps3yf.css';
import '../../css/e/ey6kym17a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="cr_qps3yf"/><path class="ey6kym17a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:circleci" {...props}></Icon>
