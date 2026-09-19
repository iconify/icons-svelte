<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dag7f4b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dag7f4b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fangs-circle" {...props}></Icon>
