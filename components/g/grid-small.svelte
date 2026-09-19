<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d976pzb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d976pzb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:grid-small" {...props}></Icon>
