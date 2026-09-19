<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wle5_hbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1568};
const content = `<path class="wle5_hbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:ban" {...props}></Icon>
