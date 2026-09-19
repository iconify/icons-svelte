<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnjzws47l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wnjzws47l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:balloon-fill" {...props}></Icon>
