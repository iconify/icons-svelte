<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leqcnbcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leqcnbcqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-left-gloss" {...props}></Icon>
