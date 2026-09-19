<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7a0pibot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7a0pibot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:factory-02" {...props}></Icon>
