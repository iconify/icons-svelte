<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paae67brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="paae67brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:hide-3" {...props}></Icon>
