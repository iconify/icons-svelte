<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmjlz_b5w.css';
import '../../css/f/f-tq-dhdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jmjlz_b5w"/><path class="f-tq-dhdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:erugo" {...props}></Icon>
