<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyh8ppbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oyh8ppbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:high-heeled-shoes" {...props}></Icon>
