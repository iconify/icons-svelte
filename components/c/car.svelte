<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r11i6spuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r11i6spuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:car" {...props}></Icon>
