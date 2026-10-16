<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn90sxb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hn90sxb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:focus-48-bold" {...props}></Icon>
