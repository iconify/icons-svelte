<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my6sclizn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="my6sclizn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ceph" {...props}></Icon>
