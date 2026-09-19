<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srjcvbbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":896};
const content = `<path class="srjcvbbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pixelchest" {...props}></Icon>
