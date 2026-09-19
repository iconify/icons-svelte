<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo3vzdbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":770,"height":1024};
const content = `<path class="xo3vzdbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:placedelete" {...props}></Icon>
