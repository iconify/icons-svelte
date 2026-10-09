<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqn0hza6d.css';
import '../../css/h/htwye9bzz.css';
import '../../css/r/rk7gs_b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bqn0hza6d"/><path class="htwye9bzz"/><path class="rk7gs_b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mirror-48-bold" {...props}></Icon>
