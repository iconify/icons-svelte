<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi2abd3jl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi2abd3jl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:eco-lab-02" {...props}></Icon>
