<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/docpr_fdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="docpr_fdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevron-down-20-bold" {...props}></Icon>
