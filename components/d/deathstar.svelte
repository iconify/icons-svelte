<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px_p7rlgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="px_p7rlgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:deathstar" {...props}></Icon>
