<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rigfyab2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rigfyab2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hashtag-small" {...props}></Icon>
