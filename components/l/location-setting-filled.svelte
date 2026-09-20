<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqze8hb0i.css';
import '../../css/x/xsi-ndbpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqze8hb0i"/><path class="xsi-ndbpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:location-setting-filled" {...props}></Icon>
