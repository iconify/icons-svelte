<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7c_5vb9e.css';
import '../../css/m/mqkco8bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s7c_5vb9e"/><path class="mqkco8bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clapperboard-48-bold" {...props}></Icon>
