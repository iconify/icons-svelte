<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/la9q-q5df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="la9q-q5df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:buffer-time-after" {...props}></Icon>
