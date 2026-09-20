<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmvw-64_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmvw-64_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-filled" {...props}></Icon>
