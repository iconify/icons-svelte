<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyxdudq_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyxdudq_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-column-decreasing-solid" {...props}></Icon>
