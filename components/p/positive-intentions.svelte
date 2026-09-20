<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra-_p7bsg.css';
import '../../css/a/acuwqsypk.css';
import '../../css/g/g-ii3kbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ra-_p7bsg"/><path class="acuwqsypk"/><path class="g-ii3kbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:positive-intentions" {...props}></Icon>
