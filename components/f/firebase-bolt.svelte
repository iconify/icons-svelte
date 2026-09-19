<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjn9d8bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":272,"height":512};
const content = `<path class="kjn9d8bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:firebase-bolt" {...props}></Icon>
