<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfwqoacpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zfwqoacpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pilgrim-hat" {...props}></Icon>
