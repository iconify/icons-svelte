<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmks9jq-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmks9jq-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minecraft-dark" {...props}></Icon>
