<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feujp6_ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feujp6_ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openwrt" {...props}></Icon>
