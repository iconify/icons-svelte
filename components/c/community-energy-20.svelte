<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubixxqbpx.css';
import '../../css/b/bkn6lndtv.css';
import '../../css/k/kkrg8z3mz.css';
import '../../css/i/icfykfbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ubixxqbpx"/><path class="bkn6lndtv"/><path class="kkrg8z3mz"/><path class="icfykfbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:community-energy-20" {...props}></Icon>
