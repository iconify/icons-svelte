<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtw1_oswe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dtw1_oswe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:desktop-computer-small" {...props}></Icon>
