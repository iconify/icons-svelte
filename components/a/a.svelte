<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go8zfqfdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="go8zfqfdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:a" {...props}></Icon>
