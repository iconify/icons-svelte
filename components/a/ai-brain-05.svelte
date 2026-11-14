<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syzgdohqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="syzgdohqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-brain-05" {...props}></Icon>
