<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8m-lundb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r8m-lundb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bitcoin-outline" {...props}></Icon>
