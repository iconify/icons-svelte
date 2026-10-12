<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhg_0dbbc.css';
import '../../css/p/pjqal2h2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bhg_0dbbc"/><path class="pjqal2h2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rabbit-48" {...props}></Icon>
