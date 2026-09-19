<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsb06sb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="nsb06sb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:quote-right-alt" {...props}></Icon>
