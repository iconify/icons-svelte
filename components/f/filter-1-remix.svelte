<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy_pu7xll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dy_pu7xll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:filter-1-remix" {...props}></Icon>
