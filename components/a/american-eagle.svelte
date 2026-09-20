<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3-9yacyq.css';
import '../../css/p/p796kerln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="i3-9yacyq"/><path class="p796kerln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:american-eagle" {...props}></Icon>
