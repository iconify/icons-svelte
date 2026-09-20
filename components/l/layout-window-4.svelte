<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv9y7lbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rv9y7lbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:layout-window-4" {...props}></Icon>
