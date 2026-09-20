<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6t6jkvfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="w6t6jkvfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:list-sorted" {...props}></Icon>
