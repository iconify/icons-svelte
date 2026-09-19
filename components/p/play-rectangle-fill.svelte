<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohonk9mbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ohonk9mbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:play-rectangle-fill" {...props}></Icon>
