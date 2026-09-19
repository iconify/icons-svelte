<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-ta6t1nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-ta6t1nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:globe" {...props}></Icon>
