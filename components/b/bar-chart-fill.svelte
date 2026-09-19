<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv-tlrbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv-tlrbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:bar-chart-fill" {...props}></Icon>
