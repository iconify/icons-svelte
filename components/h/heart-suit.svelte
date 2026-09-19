<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agydmcrgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="agydmcrgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:heart-suit" {...props}></Icon>
