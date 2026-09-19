<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0su68bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="c0su68bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:l" {...props}></Icon>
