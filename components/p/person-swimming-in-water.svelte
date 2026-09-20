<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6vkwswbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o6vkwswbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-swimming-in-water" {...props}></Icon>
