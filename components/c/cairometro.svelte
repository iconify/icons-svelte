<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vup6mgjcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vup6mgjcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cairometro" {...props}></Icon>
