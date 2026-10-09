<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmscwpj8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmscwpj8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frequency-48-bold" {...props}></Icon>
