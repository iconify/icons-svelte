<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u364xbb6d.css';
import '../../css/i/ilw_03s_n.css';
import '../../css/e/e23at5bmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u364xbb6d"/><path class="ilw_03s_n"/><path class="e23at5bmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-flexibility-20-bold" {...props}></Icon>
