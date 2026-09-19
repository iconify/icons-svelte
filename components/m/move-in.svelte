<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c83n9-b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c83n9-b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:move-in" {...props}></Icon>
