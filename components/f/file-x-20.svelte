<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-g74icta.css';
import '../../css/r/r4kevhbfq.css';
import '../../css/l/lktv4abld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="r4kevhbfq"/><path class="lktv4abld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-x-20" {...props}></Icon>
