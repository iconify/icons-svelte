<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwcpij0ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zwcpij0ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:double-take" {...props}></Icon>
