<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc4722a5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xc4722a5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:copyright" {...props}></Icon>
