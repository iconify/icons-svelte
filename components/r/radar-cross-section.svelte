<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf60shb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zf60shb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:radar-cross-section" {...props}></Icon>
