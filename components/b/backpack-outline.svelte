<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijfzrmjsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijfzrmjsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:backpack-outline" {...props}></Icon>
