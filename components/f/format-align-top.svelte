<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwe_2jbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwe_2jbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-align-top" {...props}></Icon>
