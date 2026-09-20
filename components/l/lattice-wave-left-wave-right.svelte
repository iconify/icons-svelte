<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt5i5t-vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bt5i5t-vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lattice-wave-left-wave-right" {...props}></Icon>
