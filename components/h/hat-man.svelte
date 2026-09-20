<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zi_9etbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zi_9etbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:hat-man" {...props}></Icon>
