<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnken7bpp.css';
import '../../css/p/pbgwgktza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnken7bpp"/><path class="pbgwgktza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codescan-checkmark-24" {...props}></Icon>
