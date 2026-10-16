<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvpjufbao.css';
import '../../css/f/fybrpkbhk.css';
import '../../css/l/l-srprb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fvpjufbao"/><path class="fybrpkbhk"/><path class="l-srprb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-hydro-20-bold" {...props}></Icon>
