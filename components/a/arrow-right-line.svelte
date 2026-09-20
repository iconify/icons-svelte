<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti9vqc5io.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti9vqc5io"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:arrow-right-line" {...props}></Icon>
