<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8b-edbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="z8b-edbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:earthquake" {...props}></Icon>
