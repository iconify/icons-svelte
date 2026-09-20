<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbm5cab-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbm5cab-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:keyboard-shift" {...props}></Icon>
