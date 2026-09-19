<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plnner7oi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="plnner7oi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:link-slash" {...props}></Icon>
