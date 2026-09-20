<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/v/v922nzbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="bc1fd0lxe"/><path class="v922nzbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:open-webui" {...props}></Icon>
