<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an6zuxdwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="an6zuxdwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:an-otter-wiki-light" {...props}></Icon>
