<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnzen6byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnzen6byg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cherry-filled" {...props}></Icon>
