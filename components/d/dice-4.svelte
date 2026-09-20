<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4_z15bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j4_z15bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:dice-4" {...props}></Icon>
