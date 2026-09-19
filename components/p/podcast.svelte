<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmtmf8b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="kmtmf8b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:podcast" {...props}></Icon>
