<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-76m0b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e-76m0b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-wrap-square" {...props}></Icon>
