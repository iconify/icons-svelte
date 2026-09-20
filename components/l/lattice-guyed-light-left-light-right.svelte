<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngjzxub7r.css';
import '../../css/j/j3ukne2vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ngjzxub7r"/><path class="j3ukne2vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lattice-guyed-light-left-light-right" {...props}></Icon>
