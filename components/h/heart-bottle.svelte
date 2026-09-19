<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brw53hbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="brw53hbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-bottle" {...props}></Icon>
