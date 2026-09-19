<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtj4og6cw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dtj4og6cw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:filter" {...props}></Icon>
