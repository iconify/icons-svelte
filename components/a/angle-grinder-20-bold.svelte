<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrfwqwnbz.css';
import '../../css/i/in3blmbct.css';
import '../../css/c/cg_uq7u7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vrfwqwnbz"/><path class="in3blmbct"/><path class="cg_uq7u7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:angle-grinder-20-bold" {...props}></Icon>
