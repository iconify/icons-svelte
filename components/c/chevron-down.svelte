<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egkp_3bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="egkp_3bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:chevron-down" {...props}></Icon>
