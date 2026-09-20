<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3g_wwwmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3g_wwwmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:phone-spark" {...props}></Icon>
