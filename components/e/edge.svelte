<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so6_hixzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so6_hixzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:edge" {...props}></Icon>
