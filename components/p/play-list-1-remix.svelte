<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x13w85bev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x13w85bev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:play-list-1-remix" {...props}></Icon>
