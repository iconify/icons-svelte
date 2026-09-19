<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7ls2g-va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7ls2g-va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-discord-alt" {...props}></Icon>
