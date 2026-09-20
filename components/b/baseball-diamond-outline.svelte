<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gow1o793z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gow1o793z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:baseball-diamond-outline" {...props}></Icon>
