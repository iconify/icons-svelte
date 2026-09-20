<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngjzxub7r.css';
import '../../css/u/ua61w2bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ngjzxub7r"/><path class="ua61w2bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lattice-guyed-wave-left-wave-right" {...props}></Icon>
