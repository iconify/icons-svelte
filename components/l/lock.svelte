<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6m-zls6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="x6m-zls6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:lock" {...props}></Icon>
