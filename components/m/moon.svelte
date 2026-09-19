<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im91p0gan.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="im91p0gan"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:moon" {...props}></Icon>
