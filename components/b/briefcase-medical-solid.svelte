<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2sknf2ev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="a2sknf2ev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:briefcase-medical-solid" {...props}></Icon>
