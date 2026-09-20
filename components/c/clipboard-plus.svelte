<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzkd7_b7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzkd7_b7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-plus" {...props}></Icon>
