<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5fjhy4ib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5fjhy4ib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:reply-arrow-solid" {...props}></Icon>
