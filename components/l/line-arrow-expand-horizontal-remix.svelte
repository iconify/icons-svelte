<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pupptx3cs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pupptx3cs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:line-arrow-expand-horizontal-remix" {...props}></Icon>
