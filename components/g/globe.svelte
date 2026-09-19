<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh1abjj4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mh1abjj4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:globe" {...props}></Icon>
