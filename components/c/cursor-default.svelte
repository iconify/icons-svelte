<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqnd8rbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqnd8rbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cursor-default" {...props}></Icon>
