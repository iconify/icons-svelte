<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmu1e4ohr.css';
import '../../css/d/drunhgb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zmu1e4ohr"/><path class="drunhgb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netbox" {...props}></Icon>
