<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9thckz9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9thckz9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:closed-captioning" {...props}></Icon>
