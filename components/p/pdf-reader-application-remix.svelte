<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5p67rs8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r5p67rs8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pdf-reader-application-remix" {...props}></Icon>
