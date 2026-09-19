<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rse-n5zhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="rse-n5zhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:high-voltage-sign" {...props}></Icon>
