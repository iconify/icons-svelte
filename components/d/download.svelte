<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j08bnyb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="j08bnyb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:download" {...props}></Icon>
