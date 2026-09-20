<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2rtvsbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="x2rtvsbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:link-broken" {...props}></Icon>
