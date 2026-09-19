<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu43czxoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="bu43czxoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:nfc-directional" {...props}></Icon>
