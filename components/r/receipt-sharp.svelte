<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu6zpr5jr.css';
import '../../css/c/czaquksml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zu6zpr5jr"/><path class="czaquksml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:receipt-sharp" {...props}></Icon>
