<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udiq2659b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udiq2659b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:audio-input-rca" {...props}></Icon>
