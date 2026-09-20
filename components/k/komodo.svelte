<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8a9mj15s.css';
import '../../css/r/rf0yx6n_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8a9mj15s"/><path class="rf0yx6n_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:komodo" {...props}></Icon>
