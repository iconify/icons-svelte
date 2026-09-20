<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iltdvb4kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="iltdvb4kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:folder" {...props}></Icon>
