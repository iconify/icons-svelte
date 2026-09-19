<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_hdj2l_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_hdj2l_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:location-pin-check" {...props}></Icon>
