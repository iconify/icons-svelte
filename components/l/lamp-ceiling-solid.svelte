<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn7n91bxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yn7n91bxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lamp-ceiling-solid" {...props}></Icon>
