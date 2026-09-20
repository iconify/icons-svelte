<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3oj49b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z3oj49b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:broken-link-2-solid" {...props}></Icon>
