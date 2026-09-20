<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2c8sk-0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2c8sk-0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:bed-bunk" {...props}></Icon>
