<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av0n4_bbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":319,"height":512};
const content = `<path class="av0n4_bbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:clean" {...props}></Icon>
