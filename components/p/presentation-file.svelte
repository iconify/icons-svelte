<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzhvztb2z.css';
import '../../css/q/q44zm2bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pzhvztb2z"/><path class="q44zm2bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:presentation-file" {...props}></Icon>
