<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy88r021n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fy88r021n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoiceshelf-light" {...props}></Icon>
