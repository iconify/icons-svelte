<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apca3-bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="apca3-bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:border-all" {...props}></Icon>
