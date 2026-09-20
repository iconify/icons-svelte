<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp1j6ubpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gp1j6ubpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:circle-dashed-16-solid" {...props}></Icon>
