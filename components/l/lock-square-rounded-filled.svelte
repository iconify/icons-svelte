<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i131zj91m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i131zj91m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lock-square-rounded-filled" {...props}></Icon>
