<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq_64wqcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hq_64wqcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:ripple-outline" {...props}></Icon>
