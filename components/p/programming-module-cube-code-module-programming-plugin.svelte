<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejpxn4brd.css';
import '../../css/y/yyj2mtbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ejpxn4brd"/><path class="yyj2mtbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:programming-module-cube-code-module-programming-plugin" {...props}></Icon>
