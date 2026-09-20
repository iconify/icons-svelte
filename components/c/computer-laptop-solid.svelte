<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw34_3bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw34_3bgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-laptop-solid" {...props}></Icon>
