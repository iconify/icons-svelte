<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enmz8v5ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="enmz8v5ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-rupee" {...props}></Icon>
