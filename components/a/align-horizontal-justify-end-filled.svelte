<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjpz_me_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjpz_me_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-justify-end-filled" {...props}></Icon>
