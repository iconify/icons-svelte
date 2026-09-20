<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6rr5ss6f.css';
import '../../css/s/s222euk2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6rr5ss6f"/><path class="s222euk2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nezha-dark" {...props}></Icon>
