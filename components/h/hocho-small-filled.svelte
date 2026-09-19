<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfydo-uvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="nfydo-uvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hocho-small-filled" {...props}></Icon>
