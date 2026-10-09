<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjzrwdbzw.css';
import '../../css/g/gac0p61ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hjzrwdbzw"/><path class="gac0p61ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bell-off-48-bold" {...props}></Icon>
