<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1md_z23q.css';
import '../../css/l/lo6resb1g.css';
import '../../css/n/nncz9ebus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t1md_z23q"/><path class="lo6resb1g"/><path class="nncz9ebus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-wordle" {...props}></Icon>
