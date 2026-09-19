<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbu2i64xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zbu2i64xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:haxe" {...props}></Icon>
