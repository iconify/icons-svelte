<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4tu1bc1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o4tu1bc1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:p-wide-with-arrow-right" {...props}></Icon>
