<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3olpq2tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3olpq2tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-diagonal-s-fill" {...props}></Icon>
