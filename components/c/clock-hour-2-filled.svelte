<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_d-chbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_d-chbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:clock-hour-2-filled" {...props}></Icon>
