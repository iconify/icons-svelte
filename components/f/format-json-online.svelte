<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wur179bzw.css';
import '../../css/u/ujj8k5bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="wur179bzw"/><path class="ujj8k5bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:format-json-online" {...props}></Icon>
