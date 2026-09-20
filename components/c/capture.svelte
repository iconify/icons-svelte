<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk7p9ibji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qk7p9ibji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:capture" {...props}></Icon>
