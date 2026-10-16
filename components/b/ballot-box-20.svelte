<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smusfyo3e.css';
import '../../css/g/gc1ce0bgt.css';
import '../../css/o/oexyxwbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="smusfyo3e"/><path class="gc1ce0bgt"/><path class="oexyxwbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ballot-box-20" {...props}></Icon>
