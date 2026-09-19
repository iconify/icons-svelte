<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h73t7xb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h73t7xb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:promotion" {...props}></Icon>
