<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/css7eeb7b.css';
import '../../css/s/sfw5-4b4t.css';
import '../../css/l/l8okk4b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="css7eeb7b"/><path class="sfw5-4b4t"/><path class="l8okk4b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:greenhouse-48-bold" {...props}></Icon>
