<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew__pnb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ew__pnb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-ui-settings" {...props}></Icon>
