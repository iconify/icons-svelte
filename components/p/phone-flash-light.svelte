<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkkg48bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkkg48bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:phone-flash-light" {...props}></Icon>
