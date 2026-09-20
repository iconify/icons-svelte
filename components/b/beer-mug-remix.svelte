<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8rcrgbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d8rcrgbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:beer-mug-remix" {...props}></Icon>
