<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcpvqfk3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pcpvqfk3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-down-right-20-solid" {...props}></Icon>
