<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oro_-ac7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oro_-ac7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:headphones-bluetooth" {...props}></Icon>
