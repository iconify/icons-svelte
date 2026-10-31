<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0z-jlbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a0z-jlbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crates-in-gabled-building" {...props}></Icon>
