<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6-58lbbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c6-58lbbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:robot-20-solid" {...props}></Icon>
