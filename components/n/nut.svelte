<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ba_-bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ba_-bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nut" {...props}></Icon>
