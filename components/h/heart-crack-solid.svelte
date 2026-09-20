<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en4s_dyhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en4s_dyhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-crack-solid" {...props}></Icon>
