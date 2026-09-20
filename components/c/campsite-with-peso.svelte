<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a51m0noso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a51m0noso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsite-with-peso" {...props}></Icon>
