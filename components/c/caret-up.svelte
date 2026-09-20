<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfjmi0btm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mfjmi0btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:caret-up" {...props}></Icon>
