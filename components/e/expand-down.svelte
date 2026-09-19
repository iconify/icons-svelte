<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0q3tqbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y0q3tqbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:expand-down" {...props}></Icon>
