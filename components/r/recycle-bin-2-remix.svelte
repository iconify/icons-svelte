<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_i1byt2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="r_i1byt2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:recycle-bin-2-remix" {...props}></Icon>
