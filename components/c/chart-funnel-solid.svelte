<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltl_fpnhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltl_fpnhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-funnel-solid" {...props}></Icon>
