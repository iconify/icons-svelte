<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua36r_beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ua36r_beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-rupee-filled" {...props}></Icon>
