<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl8y44ure.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl8y44ure"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:dam-filled" {...props}></Icon>
