<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny-w6qbwa.css';
import '../../css/i/iw77clbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ny-w6qbwa"/><path class="iw77clbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-code-20-bold" {...props}></Icon>
