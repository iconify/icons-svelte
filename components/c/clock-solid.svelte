<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lji_g4btr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lji_g4btr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:clock-solid" {...props}></Icon>
