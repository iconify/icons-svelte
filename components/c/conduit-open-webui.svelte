<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2_7wmb7u.css';
import '../../css/w/wdiw5pb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o2_7wmb7u"/><path class="wdiw5pb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:conduit-open-webui" {...props}></Icon>
