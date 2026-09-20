<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owf71glth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owf71glth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-remove" {...props}></Icon>
