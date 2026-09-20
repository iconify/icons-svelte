<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zae9-mbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zae9-mbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:control-d-dark" {...props}></Icon>
