<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as1j4ndtg.css';
import '../../css/q/qyo4u7bbg.css';
import '../../css/b/bc1hhwfbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="as1j4ndtg"/><path class="qyo4u7bbg"/><path class="bc1hhwfbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:goal-16" {...props}></Icon>
