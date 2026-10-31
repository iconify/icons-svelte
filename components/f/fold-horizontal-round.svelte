<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5ws0xb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5ws0xb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fold-horizontal-round" {...props}></Icon>
