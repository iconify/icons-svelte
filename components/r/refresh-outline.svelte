<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyw2t8n3g.css';
import '../../css/f/fqmfpk6cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qyw2t8n3g"/><path class="fqmfpk6cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:refresh-outline" {...props}></Icon>
