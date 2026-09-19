<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s28o16g0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s28o16g0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cherryalt" {...props}></Icon>
