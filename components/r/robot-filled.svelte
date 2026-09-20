<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e54p_3stm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e54p_3stm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:robot-filled" {...props}></Icon>
