<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je82i5n7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="je82i5n7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:round-cap-remix" {...props}></Icon>
