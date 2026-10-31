<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfhkbs4kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfhkbs4kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-turn-up-left-round" {...props}></Icon>
