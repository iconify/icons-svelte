<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uflmj6bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="uflmj6bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:road-lock" {...props}></Icon>
