<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hal7cto6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hal7cto6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:charging-station" {...props}></Icon>
