<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr3r60b7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sr3r60b7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:chess-king-solid" {...props}></Icon>
