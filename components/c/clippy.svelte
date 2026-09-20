<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9q778crg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="w9q778crg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:clippy" {...props}></Icon>
