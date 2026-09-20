<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8gfwgb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h8gfwgb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h6-20-solid" {...props}></Icon>
