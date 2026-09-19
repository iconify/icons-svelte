<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui2ki_b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ui2ki_b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:google-wallet" {...props}></Icon>
