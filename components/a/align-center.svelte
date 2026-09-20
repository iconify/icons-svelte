<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b52rwbuoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b52rwbuoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:align-center" {...props}></Icon>
