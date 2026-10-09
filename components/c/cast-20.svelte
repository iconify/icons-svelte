<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rln3ffbom.css';
import '../../css/x/xxfcmckbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rln3ffbom"/><path class="xxfcmckbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cast-20" {...props}></Icon>
