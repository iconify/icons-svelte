<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgy-j0b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="hgy-j0b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:license-plate-fill" {...props}></Icon>
