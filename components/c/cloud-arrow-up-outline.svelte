<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg7rm06cd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg7rm06cd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-arrow-up-outline" {...props}></Icon>
