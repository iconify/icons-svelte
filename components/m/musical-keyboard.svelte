<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1zxyodqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b1zxyodqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:musical-keyboard" {...props}></Icon>
