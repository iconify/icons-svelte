<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2766uktk.css';
import '../../css/l/l2dczz-db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l2766uktk"/><path class="l2dczz-db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitbundle" {...props}></Icon>
