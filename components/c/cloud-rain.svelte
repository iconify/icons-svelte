<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itg833o_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itg833o_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-rain" {...props}></Icon>
