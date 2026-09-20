<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib8o1bb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib8o1bb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-right-circle-solid" {...props}></Icon>
