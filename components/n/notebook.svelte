<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6sabc5xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="u6sabc5xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:notebook" {...props}></Icon>
