<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_7_dpb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n_7_dpb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lift-gate" {...props}></Icon>
