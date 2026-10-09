<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzy9e1bsg.css';
import '../../css/c/c_a48h94z.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kzy9e1bsg"/><path class="c_a48h94z"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-check-48" {...props}></Icon>
