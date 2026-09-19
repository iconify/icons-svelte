<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i05b62b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i05b62b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:knee-pad" {...props}></Icon>
