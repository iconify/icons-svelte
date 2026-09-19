<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psm9o272z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="psm9o272z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:bilibili-small" {...props}></Icon>
