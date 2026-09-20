<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx90f7bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bx90f7bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:medal" {...props}></Icon>
