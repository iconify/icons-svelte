<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls_du9bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls_du9bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:move-diagonal-right-filled" {...props}></Icon>
