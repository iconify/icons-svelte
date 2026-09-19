<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luecgc8hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":1024};
const content = `<path class="luecgc8hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:manalt" {...props}></Icon>
