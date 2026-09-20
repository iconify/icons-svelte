<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp8co0bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pp8co0bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-wrench" {...props}></Icon>
