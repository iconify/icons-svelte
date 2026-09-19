<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qickg1epq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qickg1epq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:curly-brackets" {...props}></Icon>
