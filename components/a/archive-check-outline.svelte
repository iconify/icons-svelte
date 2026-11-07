<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpggx48vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dpggx48vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-check-outline" {...props}></Icon>
