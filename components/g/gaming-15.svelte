<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgap1cbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tgap1cbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:gaming-15" {...props}></Icon>
