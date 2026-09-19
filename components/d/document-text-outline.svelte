<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z07rjrbqz.css';
import '../../css/v/v5_5mr8sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z07rjrbqz"/><path class="v5_5mr8sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:document-text-outline" {...props}></Icon>
