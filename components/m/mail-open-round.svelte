<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqc1w9lyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqc1w9lyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-open-round" {...props}></Icon>
