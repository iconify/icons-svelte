<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyv3t0bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wyv3t0bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:icicles-fence" {...props}></Icon>
