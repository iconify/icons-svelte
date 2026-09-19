<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhid8bcga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jhid8bcga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:rectangle" {...props}></Icon>
