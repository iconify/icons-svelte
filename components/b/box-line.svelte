<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlki94r7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlki94r7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:box-line" {...props}></Icon>
