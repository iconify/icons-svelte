<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2wxqbc6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2wxqbc6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:double-quotes-l" {...props}></Icon>
