<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipkl84b6w.css';
import '../../css/o/odbzuac1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ipkl84b6w"/><path class="odbzuac1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:globe" {...props}></Icon>
