<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8wi2x_6l.css';
import '../../css/p/pvszaybyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x8wi2x_6l"/><path class="pvszaybyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:address-book-20" {...props}></Icon>
