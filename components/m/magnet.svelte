<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4bw4gbbn.css';
import '../../css/c/czndeu-mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l4bw4gbbn"/><path class="czndeu-mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:magnet" {...props}></Icon>
