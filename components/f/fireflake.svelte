<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iji9n2szv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iji9n2szv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fireflake" {...props}></Icon>
