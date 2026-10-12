<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f22uknsdn.css';
import '../../css/j/jpnuobtcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f22uknsdn"/><path class="jpnuobtcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:megaphone-off-filled" {...props}></Icon>
