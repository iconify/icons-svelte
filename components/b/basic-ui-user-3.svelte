<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it10i7brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="it10i7brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-user-3" {...props}></Icon>
