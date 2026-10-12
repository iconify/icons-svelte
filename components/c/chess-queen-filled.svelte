<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grrye6bcq.css';
import '../../css/k/k2cjj6b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grrye6bcq"/><path clip-rule="evenodd" class="k2cjj6b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chess-queen-filled" {...props}></Icon>
