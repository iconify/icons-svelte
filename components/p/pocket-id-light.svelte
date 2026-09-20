<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao5mpybbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ao5mpybbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pocket-id-light" {...props}></Icon>
