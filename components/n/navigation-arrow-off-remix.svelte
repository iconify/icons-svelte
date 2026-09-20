<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq4s77gph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lq4s77gph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:navigation-arrow-off-remix" {...props}></Icon>
