<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhox2tbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhox2tbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:kitchen-tools" {...props}></Icon>
