<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf-m56b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uf-m56b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:calendar-star-remix" {...props}></Icon>
