<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1693cbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="v1693cbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:arpupdown" {...props}></Icon>
