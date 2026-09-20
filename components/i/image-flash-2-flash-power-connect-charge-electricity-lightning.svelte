<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5tuxwbnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j5tuxwbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:image-flash-2-flash-power-connect-charge-electricity-lightning" {...props}></Icon>
