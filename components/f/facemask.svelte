<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tchv4_7zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tchv4_7zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:facemask" {...props}></Icon>
