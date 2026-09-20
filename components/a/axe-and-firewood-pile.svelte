<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rk6i8-bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rk6i8-bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:axe-and-firewood-pile" {...props}></Icon>
