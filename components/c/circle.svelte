<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrsxhn-mv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jrsxhn-mv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:circle" {...props}></Icon>
