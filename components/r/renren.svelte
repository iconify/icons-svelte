<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5bgf6b_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j5bgf6b_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:renren" {...props}></Icon>
