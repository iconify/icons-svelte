<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0q5d6yma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0q5d6yma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:flash-off-bold" {...props}></Icon>
