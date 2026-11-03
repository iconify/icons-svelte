<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j30qxabgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="j30qxabgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:headset-20-solid" {...props}></Icon>
