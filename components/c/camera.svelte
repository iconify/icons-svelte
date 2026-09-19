<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/v/vkjbvwbld.css';
import '../../css/v/vw9h3sbzb.css';
import '../../css/z/zs6rexpdd.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRV4b4dqK"><g class="ufeehvblu"><path class="vkjbvwbld"/><rect class="vw9h3sbzb"/><path class="zs6rexpdd"/></g></mask></defs><path mask="url(#SVGRV4b4dqK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:camera" {...props}></Icon>
