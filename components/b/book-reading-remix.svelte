<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3ixh0b_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l3ixh0b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:book-reading-remix" {...props}></Icon>
