<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewat9cc6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ewat9cc6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:latex" {...props}></Icon>
