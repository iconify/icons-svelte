<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grjiqkd5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="grjiqkd5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:quotedown" {...props}></Icon>
