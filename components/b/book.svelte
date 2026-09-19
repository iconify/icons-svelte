<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja-b65-6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ja-b65-6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:book" {...props}></Icon>
