<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgh67txjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgh67txjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:calendar-gear" {...props}></Icon>
