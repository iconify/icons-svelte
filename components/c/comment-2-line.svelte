<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndlm_riwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndlm_riwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:comment-2-line" {...props}></Icon>
