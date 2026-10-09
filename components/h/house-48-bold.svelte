<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfpjugbvy.css';
import '../../css/f/fxb5cccap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="fxb5cccap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-48-bold" {...props}></Icon>
