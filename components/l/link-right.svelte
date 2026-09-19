<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5lb6ibuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x5lb6ibuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:link-right" {...props}></Icon>
