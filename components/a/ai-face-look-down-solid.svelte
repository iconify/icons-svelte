<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqh8_rbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqh8_rbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-look-down-solid" {...props}></Icon>
