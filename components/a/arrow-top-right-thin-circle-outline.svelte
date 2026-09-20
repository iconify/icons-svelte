<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw-a-7_ww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw-a-7_ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-right-thin-circle-outline" {...props}></Icon>
