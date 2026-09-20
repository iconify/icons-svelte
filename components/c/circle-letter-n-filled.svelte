<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1b637mci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1b637mci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-letter-n-filled" {...props}></Icon>
