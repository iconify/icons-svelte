<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kax94e7dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kax94e7dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:religion-muslim" {...props}></Icon>
