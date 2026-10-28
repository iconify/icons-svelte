<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avp4ev5ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="avp4ev5ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hindsight-light" {...props}></Icon>
