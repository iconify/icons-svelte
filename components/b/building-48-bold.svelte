<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwzk_6p2e.css';
import '../../css/u/uy6zwjbkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pwzk_6p2e"/><path class="uy6zwjbkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:building-48-bold" {...props}></Icon>
