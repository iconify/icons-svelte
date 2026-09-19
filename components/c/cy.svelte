<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcw1yj9nl.css';
import '../../css/o/okkvq7b7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gcw1yj9nl"/><path class="okkvq7b7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cy" {...props}></Icon>
