<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihmii9b0s.css';
import '../../css/t/t-vpait8s.css';
import '../../css/b/bbomh7bop.css';
import '../../css/b/bho8l9bjj.css';
import '../../css/w/wpjkcbchw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihmii9b0s"/><path class="t-vpait8s"/><path class="bbomh7bop"/><path class="bho8l9bjj"/><path class="wpjkcbchw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-bar-stacked-48-bold" {...props}></Icon>
