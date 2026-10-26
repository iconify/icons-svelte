<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezp-wvbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ezp-wvbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pubky" {...props}></Icon>
