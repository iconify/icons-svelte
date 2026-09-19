<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzwhn-bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="kzwhn-bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-clear-all" {...props}></Icon>
