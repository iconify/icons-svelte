<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quk-u9b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="quk-u9b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:jewelry-store-15" {...props}></Icon>
