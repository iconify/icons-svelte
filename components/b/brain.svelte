<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp9bf8b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":960};
const content = `<path class="rp9bf8b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brain" {...props}></Icon>
