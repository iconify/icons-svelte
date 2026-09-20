<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr0bolbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0bolbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clipboard-fill" {...props}></Icon>
