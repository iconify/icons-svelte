<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngjzxub7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ngjzxub7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lattice-guyed" {...props}></Icon>
