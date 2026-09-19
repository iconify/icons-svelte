<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b__1v4b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b__1v4b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bucket-wheel-excavator" {...props}></Icon>
