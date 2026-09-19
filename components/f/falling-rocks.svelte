<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1u3g-62o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p1u3g-62o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:falling-rocks" {...props}></Icon>
