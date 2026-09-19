<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a91806bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a91806bhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:folder-closed" {...props}></Icon>
