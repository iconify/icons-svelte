<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw4ku0b8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uw4ku0b8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-in-solid" {...props}></Icon>
