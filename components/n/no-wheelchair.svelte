<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_ucjj9na.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v_ucjj9na"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:no-wheelchair" {...props}></Icon>
