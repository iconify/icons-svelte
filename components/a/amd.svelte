<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx45frbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hx45frbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:amd" {...props}></Icon>
