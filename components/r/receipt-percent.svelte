<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icggw3buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icggw3buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:receipt-percent" {...props}></Icon>
