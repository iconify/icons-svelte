<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prrl5rjsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="prrl5rjsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hotel-laundry-remix" {...props}></Icon>
