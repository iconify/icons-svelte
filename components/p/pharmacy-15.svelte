<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6c8adixg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f6c8adixg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:pharmacy-15" {...props}></Icon>
