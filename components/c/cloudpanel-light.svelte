<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh_0mrb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wh_0mrb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudpanel-light" {...props}></Icon>
