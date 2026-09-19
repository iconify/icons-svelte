<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se7ex_ekk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se7ex_ekk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pilcrow" {...props}></Icon>
