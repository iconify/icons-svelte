<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2kdaybsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2kdaybsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:golf-course" {...props}></Icon>
