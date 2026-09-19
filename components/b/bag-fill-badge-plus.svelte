<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wufwabb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wufwabb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bag-fill-badge-plus" {...props}></Icon>
