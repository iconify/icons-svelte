<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpavm-beg.css';
import '../../css/p/pfluh_2pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fpavm-beg"/><path clip-rule="evenodd" class="pfluh_2pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-outline" {...props}></Icon>
