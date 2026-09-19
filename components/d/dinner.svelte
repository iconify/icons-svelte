<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbg72rhcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xbg72rhcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:dinner" {...props}></Icon>
