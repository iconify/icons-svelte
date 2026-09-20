<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-cuw3bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f-cuw3bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:justice-scale-1-solid" {...props}></Icon>
