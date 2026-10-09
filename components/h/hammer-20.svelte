<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7a1zgbqk.css';
import '../../css/d/d_mc1ovfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e7a1zgbqk"/><path class="d_mc1ovfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hammer-20" {...props}></Icon>
