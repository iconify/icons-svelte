<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl6-vpbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nl6-vpbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:grapes" {...props}></Icon>
