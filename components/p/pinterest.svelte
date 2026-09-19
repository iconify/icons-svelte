<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si_hkos6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":717};
const content = `<path class="si_hkos6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:pinterest" {...props}></Icon>
