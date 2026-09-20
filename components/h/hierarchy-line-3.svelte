<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tebc0xb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tebc0xb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:hierarchy-line-3" {...props}></Icon>
