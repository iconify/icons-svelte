<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk7sxcblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk7sxcblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:euro-circle-solid" {...props}></Icon>
