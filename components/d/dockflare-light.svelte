<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuslflzdj.css';
import '../../css/b/bep1vk00f.css';
import '../../css/t/t1hj47b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uuslflzdj"/><path class="bep1vk00f"/><path class="t1hj47b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockflare-light" {...props}></Icon>
