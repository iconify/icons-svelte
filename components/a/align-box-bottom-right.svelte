<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds8jiqaxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds8jiqaxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-box-bottom-right" {...props}></Icon>
