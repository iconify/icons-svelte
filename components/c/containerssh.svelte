<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpptukm0u.css';
import '../../css/b/bkvywwbqo.css';
import '../../css/y/ypxrjb7gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qpptukm0u"/><path class="bkvywwbqo"/><path class="ypxrjb7gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:containerssh" {...props}></Icon>
