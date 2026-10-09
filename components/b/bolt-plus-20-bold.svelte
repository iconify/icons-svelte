<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilu3h65we.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/r/r1fb64blm.css';
import '../../css/p/prfptqbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ilu3h65we"/><path class="aqsnv9bnd"/><path class="r1fb64blm"/><path class="prfptqbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-plus-20-bold" {...props}></Icon>
