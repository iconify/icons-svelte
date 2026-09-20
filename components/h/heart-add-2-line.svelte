<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydxca-bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydxca-bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:heart-add-2-line" {...props}></Icon>
