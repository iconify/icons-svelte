<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq3_x3yyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aq3_x3yyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ollama" {...props}></Icon>
