<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffhjksi5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ffhjksi5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:activepieces" {...props}></Icon>
