<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mql_dwhrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mql_dwhrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:conduit-open-webui-light" {...props}></Icon>
