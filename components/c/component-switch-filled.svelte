<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxh80fbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxh80fbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-switch-filled" {...props}></Icon>
