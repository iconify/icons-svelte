<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj9dtbbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bj9dtbbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:megaphone" {...props}></Icon>
