<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbzronb6t.css';
import '../../css/d/dok_l2b-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hbzronb6t"/><path class="dok_l2b-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chalkboard-48-bold" {...props}></Icon>
