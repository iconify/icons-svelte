<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh5gb5v9g.css';
import '../../css/u/uo0uz19so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jh5gb5v9g"/><path class="uo0uz19so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pine-tree-48" {...props}></Icon>
