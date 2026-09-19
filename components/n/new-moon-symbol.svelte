<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7vjk7b3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s7vjk7b3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:new-moon-symbol" {...props}></Icon>
