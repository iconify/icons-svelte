<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c56z29arz.css';
import '../../css/d/dj9nk1b3p.css';
import '../../css/h/hgry93bsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c56z29arz"/><path class="dj9nk1b3p"/><path class="hgry93bsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cable-lay-vessel-20-bold" {...props}></Icon>
