<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ail2dgb3l.css';
import '../../css/j/jgf7k_b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ail2dgb3l"/><path class="jgf7k_b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:maya-wordmark" {...props}></Icon>
