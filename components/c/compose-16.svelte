<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k92ore-6n.css';
import '../../css/c/cr42b6bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k92ore-6n"/><path class="cr42b6bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:compose-16" {...props}></Icon>
