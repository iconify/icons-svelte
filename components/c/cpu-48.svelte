<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hii-wibir.css';
import '../../css/n/n7h0dab1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hii-wibir"/><path class="n7h0dab1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cpu-48" {...props}></Icon>
