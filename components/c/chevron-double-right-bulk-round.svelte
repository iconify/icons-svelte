<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf2eypbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf2eypbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chevron-double-right-bulk-round" {...props}></Icon>
