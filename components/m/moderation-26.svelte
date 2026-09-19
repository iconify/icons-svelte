<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq8bp5ypx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="pq8bp5ypx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:moderation-26" {...props}></Icon>
