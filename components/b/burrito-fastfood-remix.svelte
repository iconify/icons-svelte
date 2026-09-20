<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etrsoyb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="etrsoyb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:burrito-fastfood-remix" {...props}></Icon>
