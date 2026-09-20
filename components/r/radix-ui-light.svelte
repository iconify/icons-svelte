<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_82q38za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":25,"left":4};
const content = `<path class="s_82q38za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:radix-ui-light" {...props}></Icon>
