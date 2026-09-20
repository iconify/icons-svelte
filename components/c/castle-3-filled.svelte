<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chmdl0b7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chmdl0b7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-3-filled" {...props}></Icon>
