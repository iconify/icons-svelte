<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1q54p-0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1q54p-0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:computer-desktop" {...props}></Icon>
