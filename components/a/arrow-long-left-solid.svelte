<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwmth1b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwmth1b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-left-solid" {...props}></Icon>
