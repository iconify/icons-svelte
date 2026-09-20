<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znv2t3fbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znv2t3fbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:credit-card-refund" {...props}></Icon>
