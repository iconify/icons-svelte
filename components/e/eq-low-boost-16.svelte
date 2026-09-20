<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm-51lkin.css';
import '../../css/x/x1wvsgy0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tm-51lkin"/><path class="x1wvsgy0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:eq-low-boost-16" {...props}></Icon>
