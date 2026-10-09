<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnahg-_fl.css';
import '../../css/s/s9uxlpl9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cnahg-_fl"/><path class="s9uxlpl9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jar-48-bold" {...props}></Icon>
