<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3ji_6bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h3ji_6bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-right-16" {...props}></Icon>
