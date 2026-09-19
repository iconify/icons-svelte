<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caw-axbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="caw-axbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:feather-minus-filled" {...props}></Icon>
