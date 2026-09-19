<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckx81ibjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="ckx81ibjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:counter" {...props}></Icon>
