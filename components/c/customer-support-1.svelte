<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4v6-fb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="c4v6-fb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:customer-support-1" {...props}></Icon>
