<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeurl0igg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xeurl0igg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:info" {...props}></Icon>
