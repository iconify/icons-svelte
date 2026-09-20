<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xikok5biz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xikok5biz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:attic-assets-light" {...props}></Icon>
