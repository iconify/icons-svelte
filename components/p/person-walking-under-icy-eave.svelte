<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apl3tib4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="apl3tib4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-walking-under-icy-eave" {...props}></Icon>
