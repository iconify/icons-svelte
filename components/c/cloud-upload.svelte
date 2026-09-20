<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu679icol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lu679icol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:cloud-upload" {...props}></Icon>
