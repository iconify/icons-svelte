<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqf2w1bbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mqf2w1bbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:handshake-16-solid" {...props}></Icon>
