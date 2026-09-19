<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k672c4brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k672c4brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:pinterest" {...props}></Icon>
