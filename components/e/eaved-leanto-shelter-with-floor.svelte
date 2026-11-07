<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2zl0cc2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s2zl0cc2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:eaved-leanto-shelter-with-floor" {...props}></Icon>
