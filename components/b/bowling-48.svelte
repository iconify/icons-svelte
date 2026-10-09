<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut-z-5uyn.css';
import '../../css/f/fh5ya8rmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ut-z-5uyn"/><path class="fh5ya8rmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bowling-48" {...props}></Icon>
