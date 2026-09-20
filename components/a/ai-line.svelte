<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1wks312p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1wks312p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-line" {...props}></Icon>
