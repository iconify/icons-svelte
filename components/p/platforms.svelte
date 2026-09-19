<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q92ghub-h.css';
import '../../css/k/kmch1fxsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q92ghub-h"/><path class="kmch1fxsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:platforms" {...props}></Icon>
