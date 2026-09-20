<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsto437ja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hsto437ja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:arrow-reload-horizontal-1-solid" {...props}></Icon>
