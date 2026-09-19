<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk3akactx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="yk3akactx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:info" {...props}></Icon>
