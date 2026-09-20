<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_cec3aod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r_cec3aod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:lock-semi-open-20-solid" {...props}></Icon>
