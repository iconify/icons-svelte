<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4zwxpbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="y4zwxpbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-x-mark-20-solid" {...props}></Icon>
