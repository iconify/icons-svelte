<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy49fxt8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="oy49fxt8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cloud-off-remix" {...props}></Icon>
