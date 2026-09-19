<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng3q9vbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ng3q9vbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:checked-out-by-you-12" {...props}></Icon>
