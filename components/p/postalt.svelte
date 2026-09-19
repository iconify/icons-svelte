<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjr-a-gtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zjr-a-gtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:postalt" {...props}></Icon>
