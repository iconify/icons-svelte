<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f23o3mbxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f23o3mbxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:pause" {...props}></Icon>
