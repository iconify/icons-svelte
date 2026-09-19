<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlldztbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":490,"height":512};
const content = `<path class="rlldztbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fusebox" {...props}></Icon>
