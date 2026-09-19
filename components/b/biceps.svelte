<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycy5gte1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ycy5gte1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:biceps" {...props}></Icon>
