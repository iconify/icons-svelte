<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq3i879dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="mq3i879dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:gift-alt-light" {...props}></Icon>
