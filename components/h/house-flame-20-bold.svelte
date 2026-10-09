<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1mcems0k.css';
import '../../css/h/h23ynrt8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1mcems0k"/><path class="h23ynrt8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-flame-20-bold" {...props}></Icon>
