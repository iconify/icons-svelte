<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_j1kebsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e_j1kebsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-diagonal-out-20" {...props}></Icon>
