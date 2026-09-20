<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue1jy4bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue1jy4bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:person-minus" {...props}></Icon>
