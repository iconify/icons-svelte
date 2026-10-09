<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_721kb1n.css';
import '../../css/k/k1mcwabef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o_721kb1n"/><path class="k1mcwabef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cricket-48-bold" {...props}></Icon>
