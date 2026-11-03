<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4ep1nn3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z4ep1nn3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:anchor-20-solid" {...props}></Icon>
