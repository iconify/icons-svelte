<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na2a-cbxd.css';
import '../../css/d/dxc2pxq2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na2a-cbxd"/><path class="dxc2pxq2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:juno" {...props}></Icon>
