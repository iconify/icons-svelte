<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wws_a7ftb.css';
import '../../css/n/nlzn_o26i.css';
import '../../css/u/uu38agbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wws_a7ftb"/><path class="nlzn_o26i"/><path class="uu38agbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:box-20-bold" {...props}></Icon>
