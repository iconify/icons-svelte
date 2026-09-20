<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc-2jcbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="kc-2jcbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-filter-filled" {...props}></Icon>
