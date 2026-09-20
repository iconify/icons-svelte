<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnseq_fuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnseq_fuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:replay-5-line" {...props}></Icon>
