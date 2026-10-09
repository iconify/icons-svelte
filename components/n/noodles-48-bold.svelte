<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke40ke3lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ke40ke3lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:noodles-48-bold" {...props}></Icon>
