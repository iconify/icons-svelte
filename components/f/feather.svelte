<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-vu9tbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c-vu9tbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:feather" {...props}></Icon>
