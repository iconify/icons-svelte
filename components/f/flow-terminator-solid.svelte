<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9ce0lb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l9ce0lb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-terminator-solid" {...props}></Icon>
