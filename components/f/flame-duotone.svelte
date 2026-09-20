<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcjd4sbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcjd4sbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flame-duotone" {...props}></Icon>
