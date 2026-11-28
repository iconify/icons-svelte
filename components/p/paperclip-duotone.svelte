<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3sa77ogg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary r3sa77ogg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:paperclip-duotone" {...props}></Icon>
