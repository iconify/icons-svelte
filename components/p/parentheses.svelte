<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_il24lbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="l_il24lbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:parentheses" {...props}></Icon>
