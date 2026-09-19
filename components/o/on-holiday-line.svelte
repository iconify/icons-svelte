<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcw9l3bkd.css';
import '../../css/c/cmarxq79e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="jcw9l3bkd"/><path class="cmarxq79e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:on-holiday-line" {...props}></Icon>
