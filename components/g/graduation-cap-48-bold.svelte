<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnj1uyw7u.css';
import '../../css/j/jrg8o7ldv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xnj1uyw7u"/><path class="jrg8o7ldv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:graduation-cap-48-bold" {...props}></Icon>
