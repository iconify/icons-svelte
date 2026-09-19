<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw8l5ib2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lw8l5ib2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:drone-24px" {...props}></Icon>
