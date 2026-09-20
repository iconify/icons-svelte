<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqdkc20cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdkc20cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eagle" {...props}></Icon>
