<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3nfatbmy.css';
import '../../css/l/lppl2sbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w3nfatbmy"/><path class="lppl2sbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:group-objects-save" {...props}></Icon>
