<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_acv7bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="b_acv7bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:roadtunnel" {...props}></Icon>
