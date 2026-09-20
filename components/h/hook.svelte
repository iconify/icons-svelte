<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpgxckbdv.css';
import '../../css/u/us1tjmb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpgxckbdv"/><path class="us1tjmb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hook" {...props}></Icon>
