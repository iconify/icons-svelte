<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo3513bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="eo3513bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:american-sign-language-interpreting" {...props}></Icon>
