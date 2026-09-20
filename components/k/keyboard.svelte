<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnepi1cnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnepi1cnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:keyboard" {...props}></Icon>
