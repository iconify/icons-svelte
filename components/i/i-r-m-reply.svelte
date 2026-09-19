<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v8setfb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v8setfb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:i-r-m-reply" {...props}></Icon>
