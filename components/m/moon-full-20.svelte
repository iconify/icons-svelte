<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suk0u9b4j.css';
import '../../css/v/vrixi1pns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="suk0u9b4j"/><path class="vrixi1pns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-full-20" {...props}></Icon>
