<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-1--_lvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-1--_lvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-out" {...props}></Icon>
