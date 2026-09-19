<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyyilxbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nyyilxbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:r" {...props}></Icon>
