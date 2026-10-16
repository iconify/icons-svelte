<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzxt0mswz.css';
import '../../css/f/fnuad0uhx.css';
import '../../css/k/kzyi2ibpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hzxt0mswz"/><path class="fnuad0uhx"/><path class="kzyi2ibpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-compressor-48-bold" {...props}></Icon>
