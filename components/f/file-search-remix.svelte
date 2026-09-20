<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjpr25u-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zjpr25u-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:file-search-remix" {...props}></Icon>
