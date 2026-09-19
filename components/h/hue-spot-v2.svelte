<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqb5x87ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqb5x87ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:hue-spot-v2" {...props}></Icon>
