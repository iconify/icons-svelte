<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j92jx1bzk.css';
import '../../css/a/atm69obhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j92jx1bzk"/><path class="atm69obhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-open-bold-duotone" {...props}></Icon>
