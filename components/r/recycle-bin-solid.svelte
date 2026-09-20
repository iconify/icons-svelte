<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd0vk9vgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pd0vk9vgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:recycle-bin-solid" {...props}></Icon>
