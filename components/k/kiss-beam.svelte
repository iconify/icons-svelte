<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miihutl4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="miihutl4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:kiss-beam" {...props}></Icon>
