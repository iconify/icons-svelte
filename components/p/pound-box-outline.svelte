<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrl4igb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrl4igb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pound-box-outline" {...props}></Icon>
