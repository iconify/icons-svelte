<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of_5_qxwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of_5_qxwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:play-pause" {...props}></Icon>
