<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjxe0hbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjxe0hbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:heat-advisory" {...props}></Icon>
