<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swvwx0b5q.css';
import '../../css/p/pfluh_2pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swvwx0b5q"/><path clip-rule="evenodd" class="pfluh_2pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-2-outline" {...props}></Icon>
