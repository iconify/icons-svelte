<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otpi8ybma.css';
import '../../css/r/rhawa5b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="otpi8ybma"/><path class="rhawa5b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alert-octagon-48-bold" {...props}></Icon>
