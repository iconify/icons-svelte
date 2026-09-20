<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4ph5-szq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d4ph5-szq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:microphone-16" {...props}></Icon>
