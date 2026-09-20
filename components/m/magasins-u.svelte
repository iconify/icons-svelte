<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfzel6m2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfzel6m2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:magasins-u" {...props}></Icon>
