<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj606rbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cj606rbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nordic-semiconductor" {...props}></Icon>
