<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykqcwh8cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ykqcwh8cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:floors" {...props}></Icon>
