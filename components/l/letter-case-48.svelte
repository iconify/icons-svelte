<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayrqo3blg.css';
import '../../css/g/gb1sjyb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ayrqo3blg"/><path class="gb1sjyb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:letter-case-48" {...props}></Icon>
