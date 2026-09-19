<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_5hb_i8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="g_5hb_i8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:collabtive" {...props}></Icon>
