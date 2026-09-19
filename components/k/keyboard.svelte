<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5vpu_9rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="x5vpu_9rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:keyboard" {...props}></Icon>
