<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk0_w_boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk0_w_boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:border-out" {...props}></Icon>
