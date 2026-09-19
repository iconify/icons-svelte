<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izvz7ykmk.css';
import '../../css/j/jmjkwqnaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="izvz7ykmk"/><path class="jmjkwqnaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:nutrition" {...props}></Icon>
