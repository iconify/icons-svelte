<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h27efgb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h27efgb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:greensock" {...props}></Icon>
