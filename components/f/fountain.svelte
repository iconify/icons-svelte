<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1m-5accb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t1m-5accb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:fountain" {...props}></Icon>
