<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks0phgbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks0phgbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clipboard-check-round" {...props}></Icon>
