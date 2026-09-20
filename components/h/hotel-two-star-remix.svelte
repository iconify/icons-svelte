<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my9zteq1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="my9zteq1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hotel-two-star-remix" {...props}></Icon>
