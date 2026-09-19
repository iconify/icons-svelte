<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/purrn9t8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="purrn9t8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:address-card" {...props}></Icon>
