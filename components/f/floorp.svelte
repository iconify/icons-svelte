<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4z5m5b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4z5m5b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:floorp" {...props}></Icon>
