<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl19-4ccv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sl19-4ccv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:on-sight" {...props}></Icon>
