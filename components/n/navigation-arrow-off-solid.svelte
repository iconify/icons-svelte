<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nedclxngd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nedclxngd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:navigation-arrow-off-solid" {...props}></Icon>
