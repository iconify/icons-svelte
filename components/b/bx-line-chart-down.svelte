<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve7vcj02a.css';
import '../../css/o/okcnfabkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve7vcj02a"/><path class="okcnfabkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-line-chart-down" {...props}></Icon>
