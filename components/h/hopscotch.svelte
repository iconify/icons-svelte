<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq1r-no-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mq1r-no-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:hopscotch" {...props}></Icon>
