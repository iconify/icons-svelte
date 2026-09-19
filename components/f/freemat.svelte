<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkb3kxbcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":489,"height":512};
const content = `<path class="bkb3kxbcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:freemat" {...props}></Icon>
