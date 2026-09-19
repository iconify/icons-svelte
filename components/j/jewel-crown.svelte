<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zznm4mbaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zznm4mbaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:jewel-crown" {...props}></Icon>
