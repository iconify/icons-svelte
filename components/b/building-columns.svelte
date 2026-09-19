<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzf3avl-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jzf3avl-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:building-columns" {...props}></Icon>
