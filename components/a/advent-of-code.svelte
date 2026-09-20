<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_gkd6bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_gkd6bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:advent-of-code" {...props}></Icon>
