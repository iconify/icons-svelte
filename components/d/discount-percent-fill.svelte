<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz4r9rwwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iz4r9rwwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:discount-percent-fill" {...props}></Icon>
