<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlsz-tbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlsz-tbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chart-arc" {...props}></Icon>
