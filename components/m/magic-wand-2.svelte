<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmhfi7b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jmhfi7b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:magic-wand-2" {...props}></Icon>
