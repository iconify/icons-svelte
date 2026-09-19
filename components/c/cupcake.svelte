<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i644t-bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i644t-bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cupcake" {...props}></Icon>
