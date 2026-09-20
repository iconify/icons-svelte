<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0-ck1g3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e0-ck1g3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:calculator" {...props}></Icon>
