<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_9fyk9vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="c_9fyk9vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-ignored" {...props}></Icon>
