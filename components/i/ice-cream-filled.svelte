<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmqdgf2hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmqdgf2hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ice-cream-filled" {...props}></Icon>
