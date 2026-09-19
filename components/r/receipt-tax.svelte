<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7hdcac9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7hdcac9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:receipt-tax" {...props}></Icon>
