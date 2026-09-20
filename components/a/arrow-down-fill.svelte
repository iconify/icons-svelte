<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llm-ozb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="llm-ozb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-down-fill" {...props}></Icon>
