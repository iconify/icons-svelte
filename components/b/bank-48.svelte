<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8x798baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i8x798baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bank-48" {...props}></Icon>
