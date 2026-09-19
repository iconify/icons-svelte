<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmk-81bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nmk-81bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:favicon" {...props}></Icon>
