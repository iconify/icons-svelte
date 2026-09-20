<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lalr2pbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lalr2pbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alliedmodders" {...props}></Icon>
