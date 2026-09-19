<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8oh7p4lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x8oh7p4lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:add-subset" {...props}></Icon>
