<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5s5r9buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m5s5r9buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:quadrilateral" {...props}></Icon>
