<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaapy-bnd.css';
import '../../css/z/zl8qabcpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vaapy-bnd"/><path class="zl8qabcpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raneto" {...props}></Icon>
