<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8t4grbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8t4grbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:planet-minus" {...props}></Icon>
