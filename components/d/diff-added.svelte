<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmut4uqqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="mmut4uqqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-added" {...props}></Icon>
