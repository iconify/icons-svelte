<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isy_o2iqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isy_o2iqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-up-right" {...props}></Icon>
