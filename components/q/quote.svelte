<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wblgxgr2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wblgxgr2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:quote" {...props}></Icon>
