<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs2_t7lkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs2_t7lkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pen-ai-fill" {...props}></Icon>
