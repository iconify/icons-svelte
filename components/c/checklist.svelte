<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv094-b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hv094-b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:checklist" {...props}></Icon>
