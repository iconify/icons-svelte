<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qawia2ile.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qawia2ile"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:archive-plus" {...props}></Icon>
