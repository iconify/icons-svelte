<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3tyxvb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d3tyxvb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:rdoc" {...props}></Icon>
