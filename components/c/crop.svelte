<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-o0fvoyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-o0fvoyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:crop" {...props}></Icon>
