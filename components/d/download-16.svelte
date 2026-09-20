<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-tx9_o5y.css';
import '../../css/z/zi9a-zbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-tx9_o5y"/><path class="zi9a-zbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:download-16" {...props}></Icon>
