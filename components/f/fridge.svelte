<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv3bb1bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lv3bb1bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fridge" {...props}></Icon>
