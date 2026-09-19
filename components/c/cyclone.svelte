<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2qh98usm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h2qh98usm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:cyclone" {...props}></Icon>
