<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e24y9nbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="e24y9nbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bell" {...props}></Icon>
