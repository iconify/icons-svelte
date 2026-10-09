<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oynp_94rk.css';
import '../../css/s/spuk--beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oynp_94rk"/><path class="spuk--beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-left-20-bold" {...props}></Icon>
