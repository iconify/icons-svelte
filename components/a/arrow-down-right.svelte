<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu_teqejm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cu_teqejm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:arrow-down-right" {...props}></Icon>
