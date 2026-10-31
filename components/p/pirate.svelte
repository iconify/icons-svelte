<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh2693boa.css';
import '../../css/f/f1av2wb0k.css';
import '../../css/r/ra7pdcbvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="lh2693boa"/><path class="f1av2wb0k"/><path class="ra7pdcbvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:pirate" {...props}></Icon>
