<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owps0zbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="owps0zbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:beaver" {...props}></Icon>
