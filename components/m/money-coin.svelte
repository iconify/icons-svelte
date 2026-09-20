<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwo4oxi0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uwo4oxi0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:money-coin" {...props}></Icon>
