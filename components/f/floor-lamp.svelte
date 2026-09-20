<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzned5b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zzned5b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:floor-lamp" {...props}></Icon>
