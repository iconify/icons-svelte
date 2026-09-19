<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/andt_0b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="andt_0b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:address-book-alt" {...props}></Icon>
