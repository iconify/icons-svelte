<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piwcl33hw.css';
import '../../css/z/z1hh6xrvl.css';
import '../../css/u/uo2_qkbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="piwcl33hw"/><path class="z1hh6xrvl"/><path class="uo2_qkbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:palm-tree-20" {...props}></Icon>
