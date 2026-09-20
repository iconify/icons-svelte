<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg2fob-2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mg2fob-2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clock" {...props}></Icon>
