<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqnn4pbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iqnn4pbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:diamond-48-bold" {...props}></Icon>
