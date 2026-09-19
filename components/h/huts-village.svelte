<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0_vfm_rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j0_vfm_rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:huts-village" {...props}></Icon>
