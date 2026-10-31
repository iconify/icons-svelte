<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7xtxcb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7xtxcb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-from-line-round" {...props}></Icon>
