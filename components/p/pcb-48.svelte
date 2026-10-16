<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0y49ybbx.css';
import '../../css/e/ecfpntb8u.css';
import '../../css/e/ehob8bc4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n0y49ybbx"/><path class="ecfpntb8u"/><path class="ehob8bc4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pcb-48" {...props}></Icon>
