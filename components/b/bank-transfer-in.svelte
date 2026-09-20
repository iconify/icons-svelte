<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp6px_r1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xp6px_r1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-transfer-in" {...props}></Icon>
