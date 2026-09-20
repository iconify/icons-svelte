<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq6qj3b9f.css';
import '../../css/g/g0pwxi3zt.css';
import '../../css/t/ty23m0b9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wq6qj3b9f"/><path class="g0pwxi3zt"/><path class="ty23m0b9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:langfuse" {...props}></Icon>
