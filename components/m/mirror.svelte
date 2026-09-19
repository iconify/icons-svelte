<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8co5b81d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i8co5b81d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mirror" {...props}></Icon>
