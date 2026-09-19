<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxu4mccbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="zxu4mccbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:progress-5" {...props}></Icon>
