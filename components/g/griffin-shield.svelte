<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfxtc6d7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zfxtc6d7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:griffin-shield" {...props}></Icon>
