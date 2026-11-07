<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv2tejbrr.css';
import '../../css/l/ltreopbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tv2tejbrr"/><path class="ltreopbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:exit-bold" {...props}></Icon>
