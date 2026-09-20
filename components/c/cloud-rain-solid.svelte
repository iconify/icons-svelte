<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvcoe55wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvcoe55wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-rain-solid" {...props}></Icon>
