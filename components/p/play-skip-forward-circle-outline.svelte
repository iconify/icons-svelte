<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsg5j7ibl.css';
import '../../css/v/v-v__jv0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsg5j7ibl"/><path class="v-v__jv0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:play-skip-forward-circle-outline" {...props}></Icon>
