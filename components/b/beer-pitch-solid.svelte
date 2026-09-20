<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5vgli-7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="h5vgli-7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:beer-pitch-solid" {...props}></Icon>
