<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb15imbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb15imbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-double-left-solid" {...props}></Icon>
