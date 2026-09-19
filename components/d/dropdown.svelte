<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olzgs6svr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="olzgs6svr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:dropdown" {...props}></Icon>
