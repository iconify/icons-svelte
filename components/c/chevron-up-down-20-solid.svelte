<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4aw28bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m4aw28bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-up-down-20-solid" {...props}></Icon>
