<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7lbltg1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7lbltg1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:credit-card-filled" {...props}></Icon>
