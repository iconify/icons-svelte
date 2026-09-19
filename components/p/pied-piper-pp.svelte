<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdsw_ab7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="xdsw_ab7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pied-piper-pp" {...props}></Icon>
