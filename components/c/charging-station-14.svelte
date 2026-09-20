<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-e2otb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="g-e2otb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:charging-station-14" {...props}></Icon>
