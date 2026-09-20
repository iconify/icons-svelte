<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo5h-vbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uo5h-vbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:png-outline" {...props}></Icon>
