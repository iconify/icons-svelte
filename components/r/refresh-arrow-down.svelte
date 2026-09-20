<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxdhfkbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="wxdhfkbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:refresh-arrow-down" {...props}></Icon>
