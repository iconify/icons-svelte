<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbvv7mb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="mbvv7mb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:brush" {...props}></Icon>
