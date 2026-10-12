<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggzcegw8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ggzcegw8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:info-circle-fill-20" {...props}></Icon>
