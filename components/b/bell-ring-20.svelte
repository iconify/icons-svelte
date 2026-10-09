<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrvjxe57d.css';
import '../../css/u/uh0ujnbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jrvjxe57d"/><path class="uh0ujnbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-ring-20" {...props}></Icon>
