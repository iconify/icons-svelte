<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbpddjans.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbpddjans"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:badge-minus" {...props}></Icon>
