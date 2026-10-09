<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0gbnw5mt.css';
import '../../css/n/nj8qf_mxd.css';
import '../../css/s/s8v6w-jez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s0gbnw5mt"/><path class="nj8qf_mxd"/><path class="s8v6w-jez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chicken-leg-20" {...props}></Icon>
