<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkt6sx4xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="bkt6sx4xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:inbox-box" {...props}></Icon>
