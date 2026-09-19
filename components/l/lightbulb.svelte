<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdz3fbi0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="kdz3fbi0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:lightbulb" {...props}></Icon>
