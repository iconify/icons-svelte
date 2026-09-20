<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilksgw24q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilksgw24q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:musivault-light" {...props}></Icon>
