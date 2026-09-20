<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlds2mbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlds2mbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bell-minus" {...props}></Icon>
