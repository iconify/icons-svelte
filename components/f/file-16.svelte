<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3imm0oib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b3imm0oib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-16" {...props}></Icon>
