<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rof69hb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rof69hb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:countryside-48-bold" {...props}></Icon>
