<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_v3jdmza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p_v3jdmza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:justify-right" {...props}></Icon>
