<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwwh6z39s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="xwwh6z39s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:3g" {...props}></Icon>
