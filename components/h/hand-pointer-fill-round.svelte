<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl_jc-bml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl_jc-bml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hand-pointer-fill-round" {...props}></Icon>
