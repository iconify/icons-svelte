<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3-ah3bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t3-ah3bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:basketball-15" {...props}></Icon>
