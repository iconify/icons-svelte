<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-4ia3b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-4ia3b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-more-fill" {...props}></Icon>
