<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o17f7ebdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o17f7ebdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lava-lamp" {...props}></Icon>
