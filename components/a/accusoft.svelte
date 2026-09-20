<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9_ix79gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t9_ix79gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:accusoft" {...props}></Icon>
