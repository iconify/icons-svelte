<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th5y43rma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="th5y43rma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:egg" {...props}></Icon>
