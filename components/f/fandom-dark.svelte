<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9pk-gb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q9pk-gb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fandom-dark" {...props}></Icon>
