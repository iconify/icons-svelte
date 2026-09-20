<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5yxhdbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f5yxhdbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:document-1" {...props}></Icon>
