<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i64r4w9ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i64r4w9ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-line" {...props}></Icon>
