<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr9lctgvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vr9lctgvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:fedora" {...props}></Icon>
