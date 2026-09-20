<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmxlpywrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmxlpywrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-right-solid" {...props}></Icon>
