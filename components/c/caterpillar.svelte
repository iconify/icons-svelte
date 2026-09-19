<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dunh3ea7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dunh3ea7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:caterpillar" {...props}></Icon>
