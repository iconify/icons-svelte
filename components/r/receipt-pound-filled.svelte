<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kip8j-bqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kip8j-bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-pound-filled" {...props}></Icon>
