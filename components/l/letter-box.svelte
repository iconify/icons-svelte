<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qia54wv4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qia54wv4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:letter-box" {...props}></Icon>
