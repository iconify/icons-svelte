<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omm57_y2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="omm57_y2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:block-seven" {...props}></Icon>
