<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2c71bctq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q2c71bctq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:dashboard" {...props}></Icon>
