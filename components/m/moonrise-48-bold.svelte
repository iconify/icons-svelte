<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg_2veb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="eg_2veb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moonrise-48-bold" {...props}></Icon>
