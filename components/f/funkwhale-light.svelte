<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f50387gyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f50387gyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:funkwhale-light" {...props}></Icon>
