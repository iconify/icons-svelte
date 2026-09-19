<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drne2_c5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drne2_c5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:check-mark" {...props}></Icon>
