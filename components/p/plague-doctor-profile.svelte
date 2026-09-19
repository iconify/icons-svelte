<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxzz49brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jxzz49brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plague-doctor-profile" {...props}></Icon>
