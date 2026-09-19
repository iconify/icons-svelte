<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt6hk3bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bt6hk3bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nefertiti" {...props}></Icon>
