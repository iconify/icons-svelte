<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkmq96vrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="wkmq96vrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:indent-20-solid" {...props}></Icon>
