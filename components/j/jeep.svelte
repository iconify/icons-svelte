<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-nsp2j0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c-nsp2j0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jeep" {...props}></Icon>
